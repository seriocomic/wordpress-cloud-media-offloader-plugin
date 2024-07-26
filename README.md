<!--
[![Author](https://img.shields.io/badge/author-Daniel%20M.%20Hendricks-blue.svg?colorB=9900cc&style=flat-square)](https://www.danhendricks.com/?utm_source=github.com&utm_medium=campaign&utm_content=button&utm_campaign=seriocomic%2Fwordpress-cloud-media-offloader-plugin)
[![Latest Version](https://img.shields.io/github/release/seriocomic/wordpress-cloud-media-offloader-plugin.svg?style=flat-square)](https://github.com/seriocomic/wordpress-cloud-media-offloader-plugin/releases)
[![GitHub License](https://img.shields.io/badge/license-GPLv2-yellow.svg?style=flat-square)](https://github.com/seriocomic/wordpress-cloud-media-offloader-plugin/blob/master/LICENSE)
[![Composer Downloads](https://img.shields.io/packagist/dt/seriocomic/wordpress-cloud-media-offloader-plugin.svg?style=flat-square&label=packagist)](https://packagist.org/packages/seriocomic/wordpress-cloud-media-offloader-plugin)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg?style=flat-square)](https://paypal.me/danielhendricks)
[![Flywheel](https://img.shields.io/badge/style-Flywheel-green.svg?style=flat-square&label=get%20hosted&colorB=AE2A21)](https://share.getf.ly/e25g6k?utm_source=github.com&utm_medium=campaign&utm_content=button&utm_campaign=seriocomic%2Fwordpress-cloud-media-offloader-plugin)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/seriocomic/wordpress-cloud-media-offloader-plugin.svg?style=social)](https://twitter.com/danielhendricks)
-->

# Cloud Media Offloader Plugin for WordPress

This is currently under development and contains bugs. Test in a development environment first and use at your own risk.

#### :fast_forward: Download Installable ZIP: [cloud-media-offloader.zip](https://github.com/seriocomic/wordpress-cloud-media-offloader-plugin/releases/download/0.9.0/cloud-media-offloader.zip)

## Contents

- [Description](#description)
- [Installation](#installation)
   - [Requirements](#requirements)
- [Known Compatibilities & Conflicts](#known-compatibilities--conflicts)
- [Goals](#future-goals)
- [Screenshots](#screenshots)

## Description

This is a WordPress plugin that allows you to serve your WordPress Media Library files via the [Backblaze B2](https://www.backblaze.com/b2/cloud-storage.html#af9kre) cloud storage service.

### Features

- Limit offloading by MIME types
- Option to remove files from origin server
- [Shortcode](https://github.com/seriocomic/wordpress-cloud-media-offloader-plugin/wiki/Shortcodes) to create hyperlinks and output image tags
- :new: CloudFlare support ([more info](https://www.backblaze.com/blog/backblaze-and-cloudflare-partner-to-provide-free-data-transfer/))

### Contributing

One of the best ways that you can contribute is to help me make it better, either with code or with constructive feedback. Ways to help:

* I am open to pull requests and welcome improvements.
* [Feedback](https://github.com/seriocomic/wordpress-cloud-media-offloader-plugin/issues) on how I can make it better.
* Translations (or [donations](https://paypal.me/danielhendricks) to create/maintain them)

## Installation

Download the [installable WordPress ZIP file](https://github.com/seriocomic/wordpress-cloud-media-offloader-plugin/releases/download/0.9.0/cloud-media-offloader.zip) and install via **Plugins** > **Add New** in WP Admin.

### Requirements

- WordPress 6.0 or higher
- PHP 8.0 or higher


## Known Compatibilities & Conflicts

### Known Compatibilities

* [Smush Image Compression and Optimization](https://wordpress.org/plugins/wp-smushit/)
* [Safe SVG](https://wordpress.org/plugins/safe-svg/)
* [SVG Support](https://wordpress.org/plugins/svg-support/)
* [WordPress SVG Plugin](https://github.com/Lewiscowles1986/WordPressSVGPlugin)

### Conflicts

* [Enable Media Replace](https://wordpress.org/plugins/enable-media-replace/) - Does not work when _Remove Files From Server_ is enabled.

If you encounter any conflicts, please [report them](https://github.com/seriocomic/wordpress-cloud-media-offloader-plugin/issues).
