# Reset Database

WordPress database reset tool that preserves specified plugin states after reset. This is a fork of the Reset Database plugin by MalteseSolutions.

## Features

- Resets WordPress database to default installation
- Deletes media files
- Preserves activation state of specified plugins
- Secure operation requiring admin password
- Automatic updates via Git Updater

## Installation

### Via Git Updater (Recommended)

1. Install the [Git Updater](https://git-updater.com/) plugin
2. In WordPress admin, go to Settings > Git Updater > Install Plugin
3. Enter: `https://github.com/[your-username]/reset-database`
4. Click "Install Plugin"

### Manual Installation

1. Download the latest release
2. Upload to your WordPress plugins directory
3. Activate the plugin
4. Access via Tools -> Reset Database

## Requirements

- WordPress 4.0 or higher
- PHP 7.4 or higher
- [Git Updater](https://git-updater.com/) plugin (for automatic updates)

## Configuration

To modify which plugins are preserved, edit the `$preserve_plugins` array in `reset-database.php`:

```php
private $preserve_plugins = array(
    'code-snippets/code-snippets.php',
    'git-updater/git-updater.php',
    'repoman/repoman.php',
    'reset-database-plus/reset-database.php'
);
```

## Credits

Originally created by [MalteseSolutions](http://www.maltesesolutions.com)  
Modified and enhanced by [arunsathiya](https://github.com/arunsathiya)

## License

GPLv2 or later