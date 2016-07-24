WordPress/Sage Dev Site BASH Script
===================================

Quickly spin up a local development site with a renamed [Sage](https://github.com/roots/sage) starter theme. Uses [WP-CLI](https://github.com/wp-cli/wp-cli). Creates a unique MySQL/MariaDB database & database user.

* Creates a new directory for WordPress
* Prompts for site username, site password, database user & database password
* Downloads & creates a new WordPress site, with a fresh database
* Database access is via a unique user, created by this script
* Optionally downloads, renames and activates the Sage theme
* Optionally downloads & activates the "Soil" plugin
* Optionally installs node & bower dependencies by running npm install
* Requires WP-CLI: http://wp-cli.org/

This BASH script is intended for Ubuntu 16.04 Desktop. You can modify it for use in a server environment.

## Instructions
* Ubuntu: add this script to `/usr/local/bin`
* Make it executable: `sudo chmod +x /usr/local/bin/sage-spin`
* Invoke it by typing "sage-spin" in the terminal
