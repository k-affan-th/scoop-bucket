# scoop-bucket

[Scoop](https://scoop.sh) bucket for [RightType](https://github.com/k-affan-th/RightType), a Windows tray app that fixes text typed with the wrong keyboard layout (Thai/English).

```powershell
scoop bucket add righttype https://github.com/k-affan-th/scoop-bucket
scoop install righttype
```

Update with `scoop update righttype`, remove with `scoop uninstall righttype`.

The manifest is generated from the RightType repository (`packaging/scoop.ps1`) and kept current by the Excavator workflow in `.github/workflows/excavator.yml`.
