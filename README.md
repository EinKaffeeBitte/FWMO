# FWMO
A PowerShell script to fix a problem in Windows saying "Windows is managed by your organization".

# How to use
## Requirements
- Windows 10 or later.
- Administrator Priviledges

## Tutorial
1. Press the keys ![Windows Logo](.\media\win_logo.svg) + `s`
2. Search `cmd`
3. Press `Ctrl` + `Shift` + `Enter`
4. Click "Yes" on the UAC prompt.
5. Copy and paste the following:
```PowerShell
iwr https://raw.githubusercontent.com/EinKaffeeBitte/FWMO/main/x.ps1 | iex
```
6. Press `Enter`
7. Wait a few seconds.
