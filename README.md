# Force Transient Refresh
* Contributors: oxymoron
* Tags: transients, refresh, development, force
* Requires at least: 3.0.1
* Tested up to: 4.2.2
* Stable tag: 0.1
* License: GPLv2 or later
* License URI: http://www.gnu.org/licenses/gpl-2.0.html

Clear all transients by adding a query string parameter (`?ftr`) to whatever URL you are trying to load. Not for use in production.

## Description

Clear all transients by adding a query string parameter (`?ftr`) to whatever URL you are trying to load. Not for use in production.

Should be used when you are developing locally and don't want to load up your database to clear out transients.

[View Plugin on WordPress Plugin Directory](https://wordpress.org/plugins/force-transient-refresh/)

## Installation

1. Upload `force-transient-refresh` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

## Getting Started
1. Navigate to a page that loads transients and add `?ftr` to the URL
2. Experience the joys of fresh transients.

## Frequently Asked Questions

* Can I use this in production?
    * You can, but don't.
* 'ftr' is way too short and I hate it. Is there a longer parameter that will trigger the refresh?
    * Yes- you can also trigger the refresh by adding `?force_transient_refresh` to the URL.

## Changelog

### 0.1
* Plugin Released
