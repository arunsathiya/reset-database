# Reset Database Fork

A fork of the WordPress Reset Database plugin with additional features to preserve specified plugin states after reset.

## Changes from Original

- Preserves activation state of specified plugins after database reset

## Installation

1. Download the latest release
2. Upload to your WordPress plugins directory
3. Activate the plugin
4. Access via Tools -> Reset Database

## Configuration

To modify which plugins are preserved, edit the `$preserve_plugins` array in `reset-database.php`.
