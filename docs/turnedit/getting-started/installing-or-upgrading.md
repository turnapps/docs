# Installing or Upgrading
## Install
### Download & Install in Website
1. [Click this](https://turnapps.f5.si/turnedit/download).
2. Click the download button.
3. Open explorer and then click "turnedit-setup.exe"
### Installing in command line
#### Command prompt(cmd.exe)
Type the command below(you must execute command prompt in administrator):
```batch
cd %USERPROFILE%\Downloads
curl -L https://github.com/turnapps/TurnEdit/releases/latest/download/turnedit-setup.exe -o turnedit-setup.exe
start turnedit-setup.exe
```
#### PowerShell
Type the command below(you must be execute powershell in administrator):
```powershell
Set-Location "$env:USERPROFILE\Downloads"
Invoke-WebRequest -Uri "https://github.com/turnapps/TurnEdit/releases/latest/download/turnedit-setup.exe" -OutFile "turnedit-setup.exe"
Start-Process "turnedit-setup.exe"
```
## Upgrading
1. If not opened TurnEdit, open it.
2. Navigate menu: Help > Update TurnEdit
