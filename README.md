# Skate4 Launcher Setup





<img width="664" height="337" alt="Rectangular_2026-10-05_06-11-08-489" src="https://github.com/user-attachments/assets/8d39241c-ac58-4895-aafa-6aa232cfbb8f" />



<img width="1445" height="860" alt="Rectangular_2026-10-05_06-10-34-203" src="https://github.com/user-attachments/assets/c350ca2d-9668-4f64-829b-b887dd6f3084" />




Simple native Windows app installer for the current **Skate4 Launcher**.

## What It Does

- Installs the current `Skate4Laucnher.exe` as a normal Windows application.
- Installs the launcher to your Windows user Programs folder.
- Adds **Skate4 Launcher** to the Windows Start Menu.
- Adds **Skate4 Launcher** to **Settings → Apps → Installed apps**.
- Includes a proper uninstall option.
- Can create a Desktop shortcut to the installed launcher.
- Replaces the existing launcher during Update / Repair instead of creating duplicates.
- Keeps the current Skate4 application icon.
- Keeps the current launcher splash/background.
- Removes old external launcher background files that could override the current splash.
- Prevents the launcher from replacing itself with an older launcher build.
- Does not copy, move, replace, or reinstall `ReSkate.dll`.
- Does not scan, copy, mirror, or duplicate files from your Skate4 game root.
- Does not modify your mods, projects, game files, or Steam / QR sign-in data.
- ZIP contains only `Skate4LauncherSetup.exe`.

## Install

1. Download the ZIP.
2. **Extract the ZIP first.**
3. Do not run Setup directly from inside the ZIP.
4. Run `Skate4LauncherSetup.exe`.
5. Choose the available setup options.
6. Click **Install**.
7. Wait for Setup to finish.
8. Launch **Skate4 Launcher** from the Desktop shortcut or Start Menu.

## Installed Location

The launcher is installed as a normal Windows application under:

`%LOCALAPPDATA%\Programs\Skate4 Launcher\`

The installed launcher is:

`Skate4Laucnher.exe`

Do not manually copy the installed launcher into your Skate4 game folder.

## Important — Settings File

The launcher uses:

`ReSkateLauncher.settings.json`

to store launcher preferences and saved settings.

The settings file stays with the installed launcher.

Do not manually replace it with an older copy unless you specifically want to restore older launcher settings.

## Update / Repair

Running `Skate4LauncherSetup.exe` again can update or repair the installed launcher.

Update / Repair:

- Replaces the installed launcher with the current version.
- Does not create duplicate launcher installations.
- Does not reinstall `ReSkate.dll`.
- Does not replace your Skate4 game files.
- Does not replace your mods.
- Does not copy old launcher splash files back into the installation.

## Uninstall

You can uninstall **Skate4 Launcher** normally through Windows.

Open:

**Settings → Apps → Installed apps**

Find:

**Skate4 Launcher**

Then select:

**Uninstall**

The installer includes its own uninstaller so you do not need to manually delete the application folder.

## Setup Does Not Touch

The installer does not copy, replace, move, or modify:

- `Skate.exe`
- `ReSkate.dll`
- `Mods`
- `Custom`
- `scripts`
- Steam sign-in data
- QR sign-in data
- Skate4 game-root files
- Your mod projects
- Your existing game installation

## Important

`Skate4LauncherSetup.exe` installs **Skate4 Launcher as a normal Windows application**.

It does not install Skate4 itself.

It does not install `ReSkate.dll`.

It does not duplicate your game directory.

It only installs and manages the Skate4 Launcher application.

## Platform

**Windows 10 / Windows 11 x64**

## Tags

#Skate4 #ReSkate #SkateLauncher #SkateModding #SkateMods #WindowsGaming #PCGaming #Modding #GameLauncher #SkateboardingGame
