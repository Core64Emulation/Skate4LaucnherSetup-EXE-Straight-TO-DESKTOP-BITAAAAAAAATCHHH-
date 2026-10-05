# Skate4 Launcher Setup















<img width="1913" height="944" alt="Rectangular_2026-10-05_02-49-48-107" src="https://github.com/user-attachments/assets/2fe0686f-fad0-4aca-a43b-dc91fbdc3c0c" />


<img width="601" height="738" alt="Rectangular_2026-10-05_02-02-24-737" src="https://github.com/user-attachments/assets/7dac5d2e-468d-410c-bf9e-3d1074eb7795" />

Simple native Windows installer for the current `Skate4Laucnher.exe`.

## Changes

- Installs the **exact current Skate4 launcher build** directly onto your Desktop.
- Replaces older Desktop launcher versions instead of creating duplicates.
- Removes legacy `ReSkateLauncher.exe` copies left by older installer versions.
- Uses Windows' actual Desktop known-folder path.
- Safely handles redirected or OneDrive Desktop folders.
- Tests Desktop write access before installation.
- Shows clear errors instead of silently failing.
- Verifies the installed launcher after copying.
- Keeps launcher auto-updates disabled so it cannot replace itself with an older upstream build.
- Refreshes Windows Explorer so the icon appears immediately.
- Keeps the embedded Skate4 application icon.
- Includes a native loading spinner.
- Includes a real installation progress bar.
- Includes Repair support.
- Keeps a working `Uninstall.exe` for removal through Windows Installed Apps.
- ZIP contains only `Skate4LauncherSetup.exe`.

## Install

1. Download the ZIP.
2. **Extract the ZIP first.**
3. Put the extracted `Skate4LauncherSetup.exe` somewhere safe where you will not accidentally delete it.
4. Do not run the setup directly from inside the ZIP.
5. Run `Skate4LauncherSetup.exe`.
6. Follow the installer.
7. The current `Skate4Laucnher.exe` will be installed directly onto your Desktop.
8. If an older launcher is already installed, Setup will replace it with the current version.

## Repair

Run `Skate4LauncherSetup.exe` again and choose **Repair** to restore missing launcher files and Windows registration without touching your game files, mods, or projects.

## Uninstall

Use **Windows Settings → Apps → Installed Apps → Skate4 Launcher → Uninstall**.

The registered `Uninstall.exe` removes the Skate4 Launcher files without deleting your actual Skate4 game files, mods, or custom projects.

## Platform

Windows 10 / 11 x64

ZIP integrity verified.
