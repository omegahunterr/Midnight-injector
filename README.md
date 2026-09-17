# Midnight Injector

**A lightweight Windows x86/x64 DLL loader for offline single-player modding and development.**

> [!IMPORTANT]
> Midnight Injector is intended for **offline and single-player modding, testing, and development only**.  
> It is not intended for bypassing anti-cheat systems or modifying competitive/online games.

## 📥 Download & Installation

### Requirements

- Windows 10/11
- x86 or x64 application/game
- A compatible DLL or mod
- Matching architectures:
  - **x64 process → x64 DLL**
  - **x86 process → x86 DLL**

### Installation

1. Open the **Midnight Injector** GitHub repository.
2. Go to **Releases** and select the latest version.
3. Under **Assets**, download:
   `Midnight-Injector-v1.0.0.zip`
4. Right-click the downloaded ZIP and select **Extract All**.
5. Open the extracted folder.
6. Run `MidnightInjector.exe`.

## 🚀 Usage

1. Launch your offline/single-player game or test application.
2. Open `MidnightInjector.exe`.
3. Select the target process.
4. Choose the compatible DLL/mod you want to load.
5. Confirm that the DLL architecture matches the target process.
6. Use the injector's load/inject option.

## 🛡️ Windows Security & SmartScreen

Early releases of Midnight Injector may be **unsigned**. Because of this, Windows SmartScreen or third-party security software may display an **Unknown Publisher** or **Unrecognized App** warning.

A security warning should **not automatically be treated as a false positive**.

Before running Midnight Injector:

- Download builds only from the official GitHub repository.
- Verify that the release and file are the ones you intended to download.
- Check the published **SHA-256 checksum**, when available.
- Do **not** disable Windows Security or antivirus protection globally just to run the application.

If SmartScreen appears and you have independently verified and trust the downloaded build, Windows provides **More info → Run anyway**.

## 🔐 Verify Your Download

Published releases can include a SHA-256 checksum so you can confirm that your downloaded file matches the original release.

In PowerShell:

```powershell
Get-FileHash .\Midnight-Injector-v1.0.0.zip -Algorithm SHA256
