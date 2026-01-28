# Global Library

Build your personal collection of reusable assets that can be installed into any Godot project.

## Overview

The Global Library feature lets you:

- Export any folder or addon as a `.godotpackage` file
- Store packages in a central location on your computer
- Install your packages into any project

## Setting Up the Global Folder

1. Open AssetPlus **Settings**
2. Set the **Global Asset Folder** path
3. This folder will store all your personal packages

!!! tip "Recommended Location"
    Choose a location outside your projects, like `Documents/GodotPackages/` or a cloud-synced folder for backup.

## Exporting a Package

### From FileSystem Dock

1. Right-click on any folder in the FileSystem dock
2. Select **Export as .godotpackage**
3. Fill in the metadata:
    - **Name** - Package name
    - **Version** - Version number (e.g., 1.0.0)
    - **Author** - Your name
    - **Description** - What the package contains
    - **License** - MIT, GPL, etc.
4. Optionally add a custom icon
5. Click **Export**

### Metadata

The export dialog captures:

| Field | Description |
|-------|-------------|
| Name | Display name for the package |
| Version | Semantic version (major.minor.patch) |
| Author | Creator's name |
| Description | What the package does/contains |
| License | License type |
| Icon | Custom 256x256 PNG icon |

## Installing from Global Library

1. Go to the **Global** tab in AssetPlus
2. Browse your saved packages
3. Click on a package to see details
4. Click **Install** to add it to your current project

## Package Contents

When you export a package, it includes:

- All files in the selected folder
- Input actions (if exporting an addon)
- Autoloads (if defined)
- Checksums for integrity verification

## Use Cases

- **Reusable Components** - Export UI components, utilities, or systems you use across projects
- **Backup** - Keep versioned backups of your addons
- **Sharing** - Share packages with team members
- **Templates** - Create starter templates for new projects
