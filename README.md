<img width="128" height="128" alt="mullvad-browser" src="https://github.com/user-attachments/assets/b7ea6321-0628-4d0d-9cd4-de2d01840559" />

# Mullvad Browser for Windows 8+

Mullvad Browser is a privacy-focused web browser developed in collaboration with the Tor Project to minimize fingerprinting. It is available for free and does not require a Mullvad VPN subscription to function.

Mullvad Browser 14.5.6 (based on Firefox 128.14.0 ESR) is the last version to officially support Windows 8/8.1. This repository provides a newer, patched version of Mullvad Browser, allowing users to continue using the latest features and security fixes.

<img width="1280" height="768" alt="banner" src="https://github.com/user-attachments/assets/badd9a48-49e6-4617-abdf-0c37a076a3eb" />

<hr>

# Compatibility

| Version | Windows 8.1 | Windows 8 | Windows 7 (with VxKex) | Windows 7 | Installer [.exe] | Portable [.7z] | Portable [.zip] |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 15.0.20 / ESR140.14.0 | ✅ | ✅ | ⚠️** | ❌ | N/A | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/15.0.20_ESR140.14.0/mullvadbrowser_15.0.20_ESR140.14.0_win8_installer-NFX.exe) | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/15.0.20_ESR140.14.0/mullvadbrowser_15.0.20_ESR140.14.0_win8_portable-NFX.7z) | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/15.0.20_ESR140.14.0/mullvadbrowser_15.0.20_ESR140.14.0_win8_portable-NFX.zip) |
| 16.0a5 / STD149.0a1 | ✅ | ⚠️* | ❓ | ❌ | N/A | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/16.0a5_STD149.0a1/mullvadbrowser_16.0a5_STD149.0a1_win8_portable-NFX.7z) | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/16.0a5_STD149.0a1/mullvadbrowser_16.0a5_STD149.0a1_win8_portable-NFX.zip) |
| 15.0.10 / ESR140.10.0 | ✅ | ✅ | ⚠️** | ❌ | N/A | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/15.0.10_ESR140.10.0/mullvadbrowser_15.0.10_ESR140.10.0_win8_portable-NFX.7z) | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/15.0.10_ESR140.10.0/mullvadbrowser_15.0.10_ESR140.10.0_win8_portable-NFX.zip) |
| 15.0.8 / ESR140.9.0 | ✅ | ✅ | ⚠️** | ❌ | N/A | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/15.0.8_ESR140.9.0/mullvadbrowser_15.0.8_ESR140.9.0_win8_portable-NFX.7z) | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/15.0.8_ESR140.9.0/mullvadbrowser_15.0.8_ESR140.9.0_win8_portable-NFX.zip) |
| 15.0.4 / ESR140.7.0 | ✅ | ✅ | ⚠️** | ❌ | N/A | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/15.0.4_ESR140.7.0/mullvadbrowser_15.0.4_ESR140.7.0_win8_portable-NFX.7z) | [Download](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8/releases/download/15.0.4_ESR140.7.0/mullvadbrowser_15.0.4_ESR140.7.0_win8_portable-NFX.zip) |



<hr>

> *Technically possible by using "MOZ_DISABLE_CONTENT_SANDBOX=1", however, it requires additional patching of xul.dll in order to change the instructions in SHCORE.dll "GetProcessRefenrence" to "IsOS"...

> **Possible by swapping "GetProcessRefenrence" in xul.dll (Import Directory -> SHCORE.dll) to "IsOS"... 

> k64.dll wrapper used in 16.0a5 is created by [EAZY BLACK](https://git.chefkiss.dev/WinRevived/Wrappers/releases/tag/v1.0.0).

# Not satisfied? Check out my other ports:
- [Mullvad Browser for Windows 8+](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8) - Privacy-focused web browser developed to minimize fingerprinting.
- [Tor Browser for Windows 8+](https://github.com/NiordFresh/TorBrowser-for-Windows-8) - Free, open-source web browser designed to protect user privacy and anonymity.
- [LibreWolf for Windows 8+](https://github.com/NiordFresh/LibreWolf-for-Windows-8) - Privacy-focused web browser based on Firefox, designed to enhance security.
- [Zen Browser for Windows 8+](https://github.com/NiordFresh/ZenBrowser-for-Windows-8) - Modern web browser based on the Firefox engine, designed with a focus on simplicity.

> © Powered by NiordFresh. 
