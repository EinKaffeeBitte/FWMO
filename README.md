# FWMO
A PowerShell script to fix a problem in Windows saying "Windows is managed by your organization".

# How to use
## Requirements
- Windows 10 or later.
- Administrator Priviledges

## Tutorial
1. Press the keys ![Windows Logo](.\media\win_logo.svg) + `s`
2. Search `powershell`
3. Select "Windows Powershell" (Not "Windows Powershell ISE" or "Windows Powershell x86")
4. Press `Ctrl` + `Shift` + `Enter`
5. Click "Yes" on the UAC prompt.
6. Copy and paste the following:
```PowerShell
iwr https://raw.githubusercontent.com/EinKaffeeBitte/FWMO/main/x.ps1 | iex
```
7. Press `Enter`
8. Wait a few seconds.
