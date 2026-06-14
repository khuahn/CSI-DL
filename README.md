<div align="center">

# CSI-DL - Chartswap Insights SFTP Downloader

**SFTP downloader for Chartswap Insights data. Now with a modern GUI.**

<img src="https://raw.githubusercontent.com/khuahn/CSI-DL/main/CSI1.jpg" alt="Screenshot" />

</div>

## Features

- **Graphical User Interface** — No command line needed
- **Built-in Key Editor** — Paste and save your private key directly in the app with confirmation feedback
- **Username Persistence** — SFTP username saved and auto-filled on next launch
- **Visual Status** — Buttons show Downloading / Download Complete / Key Updated at a glance
- **Compact Progress Window** — See download progress in real-time
- **Custom Download Path** — Choose where files are saved, app remembers your preference
- **Show in Folder** — Optional checkbox to auto-open the download folder when done
- **Centralized Config** — Settings and key stored in Documents, no clutter around the EXE
- **Portable** — Single EXE file, works from any folder

## Usage

1. Double-click `CSI-DL.exe`
2. Click **UPDATE PRIVATE KEY** and paste your private key, then save
3. Enter your **SFTP username**
4. Optionally, set a **Download Path** (defaults to `Downloads\CSIDL`)
5. Check **Show in folder when done** if you want the folder to open automatically
6. Click **START DOWNLOAD**
7. Close the progress window when done — your files are ready

## Requirements

- Windows 10 and Windows 11 compatible.
- No external dependencies required (OpenSSH/SFTP/.NET Framework 4.8 embedded by default)
- OPTIONAL: Downlaod PSFTP.exe or PSCP.exe. Only if things doesn't work

**Build from Source**
- PowerShell, VBScript, OpenSSH, Putty (64-bit, Auto CMD Console)

## Download

[Download Latest Release](https://github.com/khuahn/CSI-DL/releases/latest)

## Disclaimer

CSI-DL is an unofficial, non-commercial third-party tool created for ease of use. It is not affiliated with, endorsed by, or associated with Chartswap Insights in any way. This tool simply provides a simplified graphical interface for connecting to SFTP servers using credentials provided to the user, eliminating the complexity of general-purpose FTP applications like FileZilla, CyberDuck or WinSCP etc. This project is not monetized and generates no revenue. Users are responsible for ensuring their use complies with all applicable terms of service.

## License

MIT License — see [LICENSE](LICENSE) for details.
Copyright (c)2026 Khuahn

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

