<div align="center">

# CSI-DL - Chartswap Insights SFTP Downloader

**Enhanced UI/UX SFTP downloader for Chartswap Insights**

<img src="https://raw.githubusercontent.com/khuahn/CSI-DL/main/CSI1.jpg" alt="Screenshot" />

</div>

## Features

- **Graphical User Interface** — No command line required
- **Built-in Key Editor** — Paste and save private key with confirmation
- **Username Persistence** — Auto-fills saved SFTP username on launch
- **Visual Status** — Buttons indicate Downloading / Complete / Key Updated
- **Compact Progress Window** — Real-time download progress display
- **Custom Download Path** — Choose save location, app remembers preference
- **Show in Folder** — Optional auto-open of download folder after completion
- **Installer** — Single setup file, installs per-user with Desktop shortcut, no admin required

## Usage

1. Download and run `CSI-DL-Setup.exe`
2. Launch **CSI-DL** from the Desktop shortcut
3. Click **UPDATE PRIVATE KEY** and paste your private key, then save
4. Enter your **SFTP username**
5. Optionally, set a **Download Path** (defaults to `Downloads\CSIDL`)
6. Check **Show in folder when done** if you want the folder to open automatically
7. Click **START DOWNLOAD**
8. Close the progress window when done — your files are ready

## Requirements

- Windows 10 and Windows 11 compatible
- No external dependencies required (OpenSSH/SFTP/.NET Framework 4.8 embedded by default)
- OPTIONAL: Run `Install-Module -Name Posh-SSH` in PowerShell if the app fails. (RARE)

**Build from Source**
- PowerShell, VBScript, OpenSSH, Putty (64-bit, Auto CMD Console)

## DOWNLOAD
**[CSI-DL v1.8 - Stable Release](https://github.com/khuahn/CSI-DL/releases/latest)**

### ⚠️IMPORTANT!
**If you see a SmartScreen or Defender warning:**
1. Click **More info**
2. Click **Run anyway**
3. The app will install/run normally

Use the Portable version if the Installer is flagged/blocked  by SmartScreen or  Defender.
It’s a false positive and a known issue with applications compiled using Inno Setup or NSIS.
VirusTotal results: [67 of 71 vendors marked the file clean](https://www.virustotal.com/gui/file/385eb99f6c6a2ba1c039294f6a86a6e7a6a8066ac2cde74e52baf9cdc6758657).


## Disclaimer

CSI-DL is an unofficial, non-commercial third-party tool created for ease of use. It is not affiliated with, endorsed by, or associated with Chartswap Insights in any way. This tool simply provides a simplified graphical interface for connecting to SFTP servers using credentials provided to the user, eliminating the complexity of general-purpose FTP applications like FileZilla, CyberDuck or WinSCP etc. This project is not monetized and generates no revenue. Users are responsible for ensuring their use complies with all applicable terms of service.

## License

MIT License — Copyright (c)2026 Khuahn

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

