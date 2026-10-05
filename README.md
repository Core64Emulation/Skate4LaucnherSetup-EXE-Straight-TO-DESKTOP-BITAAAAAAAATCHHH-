```markdown
# Skate4 Launcher Setup

<img width="1913" height="944" alt="Skate4 Launcher" src="https://github.com/user-attachments/assets/2fe0686f-fad0-4aca-a43b-dc91fbdc3c0c" />

<img width="758" height="718" alt="Skate4 Launcher Setup" src="https://github.com/user-attachments/assets/079f2443-340a-4803-840d-225dfba6bcb4" />

Simple native Windows installer for the current `Skate4Laucnher.exe`.

## What It Does

- Installs the exact current `Skate4Laucnher.exe` directly onto your Desktop.
- Replaces an existing Desktop launcher instead of creating duplicates.
- Uses Windows' actual Desktop location.
- Supports redirected and OneDrive Desktop folders.
- Verifies the launcher after installation.
- Keeps the Skate4 application icon embedded.
- Does not copy files from the folder where Setup is launched.
- Does not scan, mirror, or duplicate your Skate4 game folder.
- Does not modify your game files, mods, projects, or Steam sign-in data.
- The ZIP contains only `Skate4LauncherSetup.exe`.

## Install

1. Download the ZIP.
2. Extract the ZIP first.
3. Keep `Skate4LauncherSetup.exe` somewhere safe.
4. Do not run Setup directly from inside the ZIP.
5. Run `Skate4LauncherSetup.exe`.
6. Follow the installer.
7. `Skate4Laucnher.exe` will be installed directly onto your Desktop.

## Important — Keep the Settings File

After installation, keep this file on your Desktop beside the launcher:

```text
ReSkateLauncher.settings.json
```

Your Desktop should look like this:

```text
Desktop\
├─ Skate4Laucnher.exe
└─ ReSkateLauncher.settings.json
```

Do **not** delete, move, or rename:

```text
ReSkateLauncher.settings.json
```

The launcher uses this file to keep your launcher preferences and saved settings between launches.

If the file is removed, the launcher may create a fresh settings file and some launcher options may reset.

For the most reliable setup, always keep these two files together on your Desktop:

```text
Skate4Laucnher.exe
ReSkateLauncher.settings.json
```

## Files Setup Does Not Touch

The installer does not copy, replace, move, or modify:

```text
Skate.exe
ReSkate.dll
Mods\
Custom\
scripts\
Steam / QR sign-in data
Game-root files
```

## Platform

**Windows 10 / 11 x64**

ZIP integrity verified.
```
