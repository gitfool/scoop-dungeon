# Scoop Bucket for Miscellaneous Tools

[![License](https://img.shields.io/github/license/gitfool/scoop-dungeon?color=blue&label=License&logo=github)](LICENSE)
[![Tests](https://img.shields.io/github/actions/workflow/status/gitfool/scoop-dungeon/ci.yml?branch=main&label=Tests&logo=github)](https://github.com/gitfool/scoop-dungeon/actions/workflows/ci.yml)
[![Excavator](https://img.shields.io/github/actions/workflow/status/gitfool/scoop-dungeon/excavator.yml?branch=main&label=Excavator&logo=github)](https://github.com/gitfool/scoop-dungeon/actions/workflows/excavator.yml)

## How do I install apps?

* Install [scoop](https://scoop.sh) ([FAQ](https://github.com/ScoopInstaller/Scoop/wiki/FAQ)) using a non-elevated [PowerShell](https://github.com/PowerShell/PowerShell):
```pwsh
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

* Add scoop [bucket](https://github.com/ScoopInstaller/Scoop/wiki/Buckets):
```pwsh
scoop bucket add dungeon https://github.com/gitfool/scoop-dungeon
```

* Install apps via scoop [cli](https://github.com/ScoopInstaller/Scoop/wiki/Commands):

| Name | Description | Command | Version |
| --- | --- | --- | --- |

## How do I update apps?

* Update scoop and apps
```powershell
scoop update && scoop update --all && scoop cleanup --all --cache
```
