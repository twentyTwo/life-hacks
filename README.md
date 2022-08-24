# life-hacks

## Extract all zip files from a folder to another folder in Windows

```powershell
Get-ChildItem "SrcPath" -Filter *.zip | Expand-Archive -DestinationPath "DestinationPath" -Force
```
