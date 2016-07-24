WordPress/Sage Dev Site BASH Script
===================================

Quickly spin up a local development site with a renamed [Sage](https://github.com/roots/sage) starter theme.

Uses [WP-CLI](https://github.com/wp-cli/wp-cli) and creates a unique MySQL/MariaDB database & database user.

The cool kids would probably do this with a Yeoman Generator, but the BASH method works pretty well. You can spin up a new site with a development theme and GitHub repo in a couple of minutes - just enter your details when prompted.

This BASH script:

* Creates a new directory for WordPress
* Prompts for site username, site password, database user & database password
* Downloads & creates a new WordPress site, with a fresh database
* Database access is via a unique user, created by this script
* Optionally downloads, renames and activates the Sage theme
* Optionally downloads & activates the "Soil" plugin
* Optionally installs node & bower dependencies by running npm install
* Optionally sets up a new GitHub repository for your project (requires GitHub token)
* Requires WP-CLI: http://wp-cli.org/

The script was developed for Ubuntu 16.04 Desktop, though I suppose it will work for most development environments that use BASH. You can modify it for use in a server environment.

## Instructions
* Ubuntu: add this script to `/usr/local/bin`
* Make it executable: `sudo chmod +x /usr/local/bin/sage-spin`
* Invoke it by typing "sage-spin" in the terminal
