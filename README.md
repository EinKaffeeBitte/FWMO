# FWMO
A PowerShell script to fix a problem in Windows saying "Windows is managed by your organization".

# How to use
## Requirements
- Windows 10 or later.
- Administrator Priviledges

## Tutorial

1. Close all applications and save your work
2. Press the keys ![Windows Logo](.\media\win_logo.svg) + `s`
3. Search `powershell`
4. Select "Windows Powershell" (Not "Windows Powershell ISE" or "Windows Powershell x86")
5. Press `Ctrl` + `Shift` + `Enter`
6. Click "Yes" on the UAC prompt.
7. Copy and paste the following:
```PowerShell
iwr https://raw.githubusercontent.com/EinKaffeeBitte/FWMO/main/x.ps1 | iex
```
8. Press `Enter`
9. Wait a few seconds
10. Close everything
11. Restart
