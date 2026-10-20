<p align="center">
  <img src="klasskonnect-mark.png" width="82" alt="KlassKonnect logo" />
</p>

<h1 align="center">KlassKonnect for Windows</h1>

<p align="center">
  Your complete school workspace, one click away.
</p>

<p align="center">
  <a href="https://isy-developer.github.io/KlassKonnect-Desktop/"><strong>Download for Windows</strong></a>
  ·
  <a href="https://www.klasskonnect.com/">Product website</a>
  ·
  <a href="SHA256SUMS.txt">Verify download</a>
</p>

<p align="center">
  <img alt="Windows 10 and 11" src="https://img.shields.io/badge/Windows-10%20%7C%2011-2563eb?style=flat-square&logo=windows11&logoColor=white" />
  <img alt="Version 0.1.0" src="https://img.shields.io/badge/version-0.1.0-0f9f91?style=flat-square" />
  <img alt="64-bit" src="https://img.shields.io/badge/platform-64--bit-0f172a?style=flat-square" />
</p>

---

## Official desktop download

This repository is the public distribution point for the KlassKonnect Windows application. It contains the installer and download-page assets only. The application source, school data, infrastructure configuration and private credentials are maintained in separate private systems.

### Install

1. Open the [official download page](https://isy-developer.github.io/KlassKonnect-Desktop/).
2. Select **Download for Windows**.
3. Open `KlassKonnectSetup.exe` and complete the installer.
4. Launch KlassKonnect and sign in securely through your browser.

## What the desktop app provides

- Direct access to your KlassKonnect role workspace
- The same live classes, timetables, files and messages as the web platform
- Secure browser-based authentication
- Automatic routing to the correct school and role after sign-in
- A focused desktop experience without the marketing website

## System requirements

| Requirement | Supported |
| --- | --- |
| Operating system | Windows 10 or Windows 11 |
| Architecture | 64-bit |
| Internet | Required for live school data |
| Account | A valid KlassKonnect school account |

## Release status

The current build is **KlassKonnect 0.1.0**, provided for the controlled school pilot. Updates will be published here after they pass product and workflow testing.

## Verify your download

The official SHA-256 value is published in [`SHA256SUMS.txt`](SHA256SUMS.txt). In PowerShell, verify the downloaded installer with:

```powershell
Get-FileHash .\KlassKonnectSetup.exe -Algorithm SHA256
```

Only install a file whose checksum matches the value published in this repository.

## Security and privacy

The installer does not contain school records. KlassKonnect retrieves permitted data after sign-in and applies the same role-based access controls as the web platform.

For product information, demo bookings and legal policies, visit [klasskonnect.com](https://www.klasskonnect.com/).
