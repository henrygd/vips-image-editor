# VIPS Image Editor

High performance WordPress image processing with [VIPS](https://libvips.github.io/libvips/).

Forked from https://github.com/CreunaFI/vips-image-editor (thanks!)

## Requirements

- PHP 7 or later
- vips package installed on your Linux system
- vips PHP extension

## Installation

1. Install vips on your system. On Ubuntu, this can be done using `apt install libvips-dev`
2. Install vips extension using [pecl](https://pecl.php.net/), this can be done with command `pecl install vips`
3. Enable PHP extension, this is usually done by adding the line `extension=vips.so` to `php.ini`
4. Download the latest plugin version from the [releases tab](https://github.com/henrygd/vips-image-editor/releases)
5. Extract the plugin under `wp-content/plugins`
6. Enable the plugin in WordPress admin interface
