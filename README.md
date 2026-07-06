# Scoop bucket for emprise

[Scoop](https://scoop.sh) bucket for the **emprise** CLI on Windows.

```powershell
scoop bucket add emprise https://github.com/pounceapps/scoop-bucket
scoop install emprise
```

Update later with:

```powershell
scoop update emprise
```

`scoop update` resolves the latest GitHub release automatically (the manifest
uses `checkver`/`autoupdate`), so this bucket tracks new emprise releases
without manual edits.

Other platforms: macOS/Linux use Homebrew (`brew install pounceapps/tap/emprise`)
or the installer at <https://emprise.dev>. See the
[install docs](https://github.com/pounceapps/emprise-app/wiki/Installation).
