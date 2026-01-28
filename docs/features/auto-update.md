# Auto-Update

AssetPlus can automatically check for updates and install them with one click.

## How It Works

1. On startup, AssetPlus checks GitHub for the latest release
2. If a newer version is available, a dialog appears
3. You can install immediately or dismiss for later

## Update Dialog

When an update is available, you'll see:

- Current version vs. new version
- Release notes (what's new)
- **Install Now** - Downloads and installs the update
- **Later** - Closes the dialog (will check again next startup)
- **Disable Auto-Update** - Stops checking at startup

## Installing Updates

When you click **Install Now**:

1. The new version is downloaded from GitHub
2. Files are extracted to a temporary location
3. The plugin is disabled
4. Old files are replaced with new ones
5. The plugin is re-enabled
6. Godot editor restarts automatically

!!! note "Editor Restart"
    The editor will restart after installing an update. Make sure to save your work before updating.

## Manual Update Check

You can manually check for updates:

1. Open AssetPlus **Settings**
2. Click **Check for Updates**
3. If an update is available, the same dialog appears

## Disabling Auto-Update

To stop automatic update checks:

**Option 1:** From the update dialog
- Click **Disable Auto-Update**
- Confirm in the popup

**Option 2:** From Settings
- Open Settings
- Uncheck **Check for updates at startup**
- Click Save

## Re-enabling Auto-Update

1. Open Settings
2. Check **Check for updates at startup**
3. Click Save

## Update Source

Updates are fetched from:
[github.com/moongdevstudio/AssetPlus/releases](https://github.com/moongdevstudio/AssetPlus/releases)

You can always download updates manually from there if auto-update fails.
