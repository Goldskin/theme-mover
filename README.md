# === Theme Mover ===
Plugin Name: Theme Mover
Version: 1.0.0
Requires at least: 2.9.0
Tested up to: 4.5
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Provides an additional location for themes. You don't need the creat the directory.

## == Installation ==

1. Upload `/theme-mover/` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Move your(s) theme(s) inside the new folder


## == Option ==

Change the var $myFolder inside index.php if you want a different directory

```php
// change the name of your directory here
$myFolder = 't';
```
