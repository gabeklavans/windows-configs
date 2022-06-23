# Commands to Do Stuff

## Windows Term/Powershell
```
Set-ExecutionPolicy RemoteSigned
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser
```

```
mklink %USERPROFILE%\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json %USERPROFILE%\windows-configs\windows-terminal.json
```

```
mklink %USERPROFILE%\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1 %USERPROFILE%\windows-configs\Microsoft.PowerShell_profile.ps1
```

## Rainmeter

```
mklink %USERPROFILE%\AppData\Roaming\Rainmeter\Rainmeter.ini %USERPROFILE%\windows-configs\Rainmeter\Rainmeter.ini
```

```
mklink /D %USERPROFILE%\AppData\Roaming\Rainmeter\Layouts %USERPROFILE%\windows-configs\Rainmeter\Layouts
```

## PowerToys
### Windows 10
```
mklink %LocalAppData%\Microsoft\PowerToys\FancyZones\zones-settings.json %USERPROFILE%\windows-configs\zones-settings.json
```
### Windows 11
```
mklink /D %LocalAppData%\Microsoft\PowerToys\FancyZones %USERPROFILE%\windows-configs\FancyZones
```