# HakureiPE HCT

Windows Portable Environment Recovery with HFS+ Support. It is a Windows 10 based Live USB Environment and dedicated to providing more flexible Windows PC maintenance experience.

Table of contents

- [Requirement](#requirement)
- [Download](#download)
- [Changelog](#changelog)
- [Credits](#credits)

## Requirement

- CPU
  - Minimal
    - `x86` / `x64` / `Arm64`
  - Recommend
    - `x86` / `x64` / `Arm64`

- RAM
  - Minimal / Size
    - `x86` / `1GB`
    - `x64` / `2GB`
    - `ARM64` / `2GB`
  - Recommend / Size
    - `x86` / `2GB`
    - `x64` / `8GB`
    - `ARM64` / `6GB`
  
- Motherboard
  - Minimal / Supports
    - `x86` / Supports boot from USB and Legacy/ia32-based UEFI
    - `x64` / Supports boot from USB and Legacy/ia32-based UEFI
    - `ARM64` / Supports boot from USB and UEFI  

  - Recommend / Supports
    - `x86` / Supports boot from USB and Legacy/ia32-based UEFI
    - `x64` / Supports boot from USB and Legacy/ia32-based UEFI
    - `ARM64` / Supports boot from USB and UEFI
  
  - Others
    - Graphics / Run on any GPU
    - Resolution Support / min: `1024×768` or higher, recommend: `1920×1080` or higher

### Download

Images has been split to multiple files. We need to merge after all files successfully downloaded.

- Clone

    ```zsh
    git clone https://github.com/theofficialcopypaste/HakureiPE-HCT.git
    ```

![Screenshot 2023-01-26 at 10 15 40 PM](https://user-images.githubusercontent.com/72515939/214858606-7d72c0fa-344e-4570-8635-b7658780090b.png)

- Merge using any archive / compress tool. ie: `zip`, `7zip` or `keka` etc)

## Changelog

- Component:Dism++ 10.1.1002.1
- DiskGenius 5.4.6.1432, CPU-Z 2.02
- VirtualHere USB Client 5.3.9
- WinNTSetup 5.2.6
- macOS HFS+ Loader

## Credits

[HikariPE](https://hikaricalyx.com/hikaripe/)
