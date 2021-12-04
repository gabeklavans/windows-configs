# Commands to Do Stuff

## Windows Term/Powershell
```
Set-ExecutionPolicy RemoteSigned
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser
```

```
mklink C:\Users\gabek\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json C:\Users\gabek\windows-configs\windows-terminal.json
```

```
mklink C:\Users\gabek\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1 C:\Users\gabek\windows-configs\Microsoft.PowerShell_profile.ps1
```

## Rainmeter

```
mklink C:\Users\gabek\AppData\Roaming\Rainmeter\Rainmeter.ini C:\Users\gabek\windows-configs\Rainmeter\Rainmeter.ini
```

```
mklink /D C:\Users\gabek\AppData\Roaming\Rainmeter\Layouts C:\Users\gabek\windows-configs\Rainmeter\Layouts
```

## PowerToys
```
mklink %LocalAppData%\Microsoft\PowerToys\FancyZones\zones-settings.json C:\Users\gabek\windows-configs\zones-settings.json
```