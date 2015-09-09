#WordPress/Sage Dev Site BASH Script

Quickly spin up a local development site.

* Creates a new directory for a WordPress site in /var/www.
* Creates a new WordPress test site, with a fresh database.
* Downloads, renames and activates the Roots theme.
* Downloads & activates the "Soil" plugin.
* Installs node & bower dependencies by running npm install.
* Requires WP-CLI: http://wp-cli.org/

This BASH script was written for Ubuntu desktop machines - I use it regularly on Ubuntu 14.04.

##Instructions
Ubuntu: add this script to `/usr/local/bin`
Make it executable: `sudo chmod +x /usr/local/bin/sage-spin`
Invoke it by typing "sage-spin" in the terminal.
