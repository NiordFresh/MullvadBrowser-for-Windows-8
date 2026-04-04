<img width="128" height="128" alt="mullvad-browser" src="https://github.com/user-attachments/assets/b7ea6321-0628-4d0d-9cd4-de2d01840559" />

# Mullvad Browser for Windows 8+

Mullvad Browser is a privacy-focused web browser developed in collaboration with the Tor Project to minimize fingerprinting. It is available for free and does not require a Mullvad VPN subscription to function.

Mullvad Browser 14.5.6 (based on Firefox 128.14.0 ESR) is the last version to officially support Windows 8/8.1. This repository provides a newer, patched version of Mullvad Browser, allowing users to continue using the latest features and security fixes.

<img width="1366" height="768" alt="banner" src="https://github.com/user-attachments/assets/a849cd0c-a80b-4f18-b571-8796da0e3d7c" />
<hr>

# Compatibility

| Version | Windows 8.1 | Windows 8 | Windows 7
| ------------- | ------------- | ------------- | ------------- |
| 15.0.4 / ESR140.7.0 | ✅ | ✅ | ❌ |
| 15.0.8 / ESR140.9.0 | ✅ | ✅ | ❌ |
| 16.0a5 / STD149.0a1 | ✅ | ⚠️* | ❌ |

<hr>

> *Technically possible by using "MOZ_DISABLE_CONTENT_SANDBOX=1", however, it requires additional patching of xul.dll in order to change the instructions in SHCORE.dll "GetDpiForMonitor" and "GetScaleFactorForMonitor" to "IsOS"... 

> k64.dll wrapper used in 16.0a5 is created by (EAZY BLACK)[https://git.chefkiss.dev/WinRevived/Wrappers/releases/tag/v1.0.0].
