<div align="center">

# CSI-DL - Chartswap Insights SFTP Downloader

**Enhanced UI/UX SFTP downloader for Chartswap Insights**

<img src="https://raw.githubusercontent.com/khuahn/CSI-DL/main/CSI.jpg" alt="Screenshot" width="480"/>

</div>

## Features

- **Graphical User Interface** — No command line required
- **Direct Key Input** — Paste your private key right on the main screen, no popups or extra buttons
- **Session-Based Credentials** — Username and key stay active while the app is open, cleared on close for security
- **Compact Progress Window** — Real-time download progress display
- **Custom Download Path** — Choose save location, app remembers your preference
- **Show in Folder** — Optional auto-open of download folder after completion
- **Installer & Portable** — Full installer with Desktop shortcut, or standalone portable version
- **No Admin Required** — Installs and runs without administrator privileges

## Usage

1. Download and run `CSI-DL_Installer.exe`
2. Launch **CSI-DL** from the Desktop shortcut
3. Paste your **private key** directly into the "Paste private key here..." field
4. Enter your **SFTP username** in the "Enter SFTP username..." field
5. Optionally, set a **Download Path** (defaults to `Downloads\CS-Insights\`)
6. Check **Show in folder when done** if you want the folder to open automatically
7. Click **START DOWNLOAD**
8. Close the progress window when done — your files are ready

## Requirements

- Compatible for both Windows 10/11, x86 or x64
- No external dependencies required (OpenSSH/SFTP/.NET Framework 4.8 embedded by default)
- OPTIONAL: Run `Install-Module -Name Posh-SSH` in PowerShell if the app fails. (RARE)

**Build from Source**
- PowerShell, VBScript, OpenSSH, Putty (64-bit, Auto CMD Console)

## ⏬ DOWNLOAD: **[<ins>CSI-DL — Latest Release</ins>](https://github.com/khuahn/CSI-DL/releases)**

**Donate:** [Buy Me a Coffee!](https://paypal.me/khuahn)

## Disclaimer

CSI-DL is an unofficial, non-commercial third-party tool created for ease of use. It is not affiliated with, endorsed by, or associated with Chartswap Insights in any way. This tool simply provides a simplified graphical interface for connecting to SFTP servers using credentials provided to the user, eliminating the complexity of general-purpose FTP applications like FileZilla, CyberDuck or WinSCP etc. This project is not monetized and generates no revenue. Users are responsible for ensuring their use complies with all applicable terms of service.

## License

MIT License — Copyright (c)2026 Khuahn

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

