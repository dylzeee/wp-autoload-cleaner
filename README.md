# WP Autoload Cleaner

**Contributors:** Dylan Jackson
**Tags:** performance, optimization, database, options, cleanup  
**Requires at least:** 5.0  
**Tested up to:** 6.4  
**Stable tag:** 1.0  
**Requires PHP:** 7.4  
**License:** GPLv2 or later  
**License URI:** https://www.gnu.org/licenses/gpl-2.0.html

WP Autoload Cleaner is a powerful tool to manage, clean, and optimize autoloaded options in your WordPress database for better performance.

---

## Features

- View all autoloaded options sorted by size.
- Detect potentially unused autoloaded options.
- Manage and delete transients with ease.
- Clean, tabbed user interface for easy navigation.

---

## Installation

1. Download the plugin as a `.zip` file or install directly from the WordPress Plugin Directory.
2. Navigate to `Plugins > Add New` in your WordPress dashboard.
3. Click `Upload Plugin`, select the downloaded file, and click `Install Now`.
4. Activate the plugin via the `Plugins` menu.

---

## Usage

1. After activating the plugin, navigate to `Tools > WP Autoload Cleaner`.
2. Use the tabs to explore:
   - **All Autoloaded Options**: View all options set to autoload.
   - **Potentially Unused Options**: Identify autoloaded options that may no longer be needed.
   - **Transients**: View and delete transients with a single click.
3. **Warning**: Only delete options or transients if you're confident they are unused or unnecessary. Deleting critical options may break your site.

---

## Frequently Asked Questions (FAQ)

### What are autoloaded options?

Autoloaded options are database entries that load automatically on every WordPress request. Cleaning unused autoloaded options can improve your site's performance.

### Is it safe to delete autoloaded options?

Only delete options if you're certain they are unused. Removing critical options may break your site. Always back up your database before making changes.

### Can this plugin delete transients?

Yes! You can delete individual transients or bulk-remove all transients via the Transients tab.

---

## Changelog

### 1.0

- Initial release with the following features:
  - Tabbed admin interface.
  - View and manage autoloaded options.
  - Detect and delete unused options.
  - Manage and bulk-delete transients.

---

## License

This plugin is licensed under the GPLv2 or later. See GPLv2 License (https://www.gnu.org/licenses/gpl-2.0.html) for more details.

---

## Future Updates

Planned features include:

- Automatic backups before deletions.
- Scheduled cleanup tasks.
- Enhanced detection for unused options.

---

## Support

If you encounter issues or have questions, please submit an issue.
